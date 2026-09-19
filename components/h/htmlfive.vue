<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgxn-yw5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":896,"height":1024};
const content = `<path class="hgxn-yw5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:htmlfive" /></template>
