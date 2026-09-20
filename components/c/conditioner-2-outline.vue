<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bs749jbzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bs749jbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:conditioner-2-outline" /></template>
