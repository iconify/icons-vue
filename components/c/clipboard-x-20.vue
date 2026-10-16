<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xb3dnqqxo.css';
import '../../css/r/rsg8pgg3u.css';
import '../../css/x/x58z-5d-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xb3dnqqxo"/><path class="rsg8pgg3u"/><path class="x58z-5d-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clipboard-x-20" /></template>
