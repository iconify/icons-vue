<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr_jcmkbu.css';
import '../../css/k/k589qfbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qr_jcmkbu"/><path clip-rule="evenodd" class="k589qfbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:device-phone-mobile-16-solid" /></template>
