<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py2qzq0bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py2qzq0bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:discourse" /></template>
