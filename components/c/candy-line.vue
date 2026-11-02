<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzr7x7b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzr7x7b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:candy-line" /></template>
