<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3n348bsq.css';
import '../../css/r/rh2mivbrm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3n348bsq"/><path class="rh2mivbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-africa" /></template>
