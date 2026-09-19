<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nb72zx0al.css';
import '../../css/h/hf-vc2b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb72zx0al"/><path class="hf-vc2b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hospital" /></template>
