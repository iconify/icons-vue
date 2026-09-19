<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqg5a0bzs.css';
import '../../css/d/dzfumybez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqg5a0bzs"/><path class="dzfumybez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:eye-off-outline" /></template>
