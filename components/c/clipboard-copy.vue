<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-4cnx5nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h-4cnx5nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:clipboard-copy" /></template>
