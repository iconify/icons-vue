<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlxtq4bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlxtq4bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jouav" /></template>
