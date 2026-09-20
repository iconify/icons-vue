<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb6xbbopk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb6xbbopk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cowbell-24" /></template>
