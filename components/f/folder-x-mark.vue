<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwbb1jbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwbb1jbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:folder-x-mark" /></template>
