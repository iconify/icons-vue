<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnzy3hbtk.css';
import '../../css/k/kyzmhfbwr.css';
import '../../css/u/uby945npi.css';
import '../../css/e/ethvzbbdu.css';
import '../../css/o/o90v17boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lnzy3hbtk"/><path class="kyzmhfbwr"/><path class="uby945npi"/><path class="ethvzbbdu"/><path class="o90v17boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:googlecloud-wordmark" /></template>
