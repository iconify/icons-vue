<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvup3bmvu.css';
import '../../css/q/qt8ow3bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvup3bmvu"/><path class="qt8ow3bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:kick-24" /></template>
