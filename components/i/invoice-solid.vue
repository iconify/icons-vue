<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eaa4jc92m.css';
import '../../css/g/g2fn-72eb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eaa4jc92m"/><path clip-rule="evenodd" class="g2fn-72eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:invoice-solid" /></template>
