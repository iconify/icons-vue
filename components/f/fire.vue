<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5gdpl4fa.css';
import '../../css/i/if6xh6bvd.css';
import '../../css/y/yo7go3bgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z5gdpl4fa"/><path class="if6xh6bvd"/><path class="yo7go3bgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:fire" /></template>
