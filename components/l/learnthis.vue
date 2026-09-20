<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9vps2b8q.css';
import '../../css/i/i2nyp1b4x.css';
import '../../css/n/n3xsaaczl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":45,"height":45};
const content = `<path class="c9vps2b8q"/><path class="i2nyp1b4x"/><path class="n3xsaaczl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:learnthis" /></template>
