<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lg43xbcaj.css';
import '../../css/i/itvcutb8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lg43xbcaj"/><path class="itvcutb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:inbox-solid" /></template>
