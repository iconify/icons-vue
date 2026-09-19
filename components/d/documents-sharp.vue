<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyexnnu5k.css';
import '../../css/r/rug9-jejd.css';
import '../../css/c/cm5ecor1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lyexnnu5k"/><path class="rug9-jejd"/><path class="cm5ecor1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:documents-sharp" /></template>
