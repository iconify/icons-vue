<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb5b0n5vc.css';
import '../../css/b/bcvzlnbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mb5b0n5vc"/><path class="bcvzlnbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:freshrss" /></template>
