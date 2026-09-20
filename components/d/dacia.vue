<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if7isuita.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if7isuita"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dacia" /></template>
