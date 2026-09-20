<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kw-tp1bar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw-tp1bar"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:folder-open-24" /></template>
