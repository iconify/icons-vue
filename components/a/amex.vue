<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo1k5b-e.css';
import '../../css/w/wku3mccqo.css';
import '../../css/t/tmnq0f59p.css';
import '../../css/q/qtouc3b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="wku3mccqo"/><path class="tmnq0f59p"/><path class="qtouc3b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:amex" /></template>
