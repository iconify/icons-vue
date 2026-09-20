<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phqcd--ip.css';
import '../../css/n/n5tl80b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="phqcd--ip"/><path class="n5tl80b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:godonateme-dark" /></template>
