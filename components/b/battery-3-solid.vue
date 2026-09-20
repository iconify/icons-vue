<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvt8_wbay.css';
import '../../css/x/xxvlnybzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="qvt8_wbay"/><path class="xxvlnybzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:battery-3-solid" /></template>
