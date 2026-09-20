<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pscmmybmb.css';
import '../../css/k/kfr1grbjb.css';
import '../../css/y/y4ucstbhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pscmmybmb"/><path class="kfr1grbjb"/><circle class="y4ucstbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:instagram-original" /></template>
