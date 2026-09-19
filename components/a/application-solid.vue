<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3s99mbew.css';
import '../../css/u/ufi4okb0l.css';
import '../../css/k/k0z7a6b-h.css';
import '../../css/t/tcbb08bkr.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 l3s99mbew"/><path class="clr-i-solid clr-i-solid-path-2 ufi4okb0l"/><path class="clr-i-solid clr-i-solid-path-3 k0z7a6b-h"/><path class="clr-i-solid clr-i-solid-path-4 tcbb08bkr"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:application-solid" /></template>
