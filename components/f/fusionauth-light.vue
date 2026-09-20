<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr3lh1bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mr3lh1bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fusionauth-light" /></template>
