<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbo0hyrvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbo0hyrvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:indent" /></template>
