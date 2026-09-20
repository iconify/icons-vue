<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbo-p0bup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbo-p0bup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:linux-foundation" /></template>
