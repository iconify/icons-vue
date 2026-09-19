<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dul5rebap.css';
import '../../css/w/wcgje-bvn.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 dul5rebap"/><path class="clr-i-solid clr-i-solid-path-2 wcgje-bvn"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:devices-solid" /></template>
