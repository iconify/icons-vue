<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofk05cbfv.css';
import '../../css/p/p7hyuf70f.css';
import '../../css/j/j8mjksuyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ofk05cbfv"/><path class="p7hyuf70f"/><path class="j8mjksuyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calculator" /></template>
