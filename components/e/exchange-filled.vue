<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5_b2ukoj.css';
import '../../css/i/i2im_ubvg.css';
import '../../css/z/znj8j9blt.css';
import '../../css/a/ajshiibhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5_b2ukoj"/><path clip-rule="evenodd" class="i2im_ubvg"/><path class="znj8j9blt"/><path clip-rule="evenodd" class="ajshiibhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:exchange-filled" /></template>
