<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipo4v_b4w.css';
import '../../css/m/mngh2w-cy.css';
import '../../css/q/qr-5js_2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipo4v_b4w"/><path class="mngh2w-cy"/><path class="qr-5js_2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kchat-dark" /></template>
