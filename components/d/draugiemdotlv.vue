<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm5q-ob1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm5q-ob1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:draugiemdotlv" /></template>
