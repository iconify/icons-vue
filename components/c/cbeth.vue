<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxzv7ug8a.css';
import '../../css/g/gam-p8bqe.css';
import '../../css/e/ece3hyfmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxzv7ug8a"/><path class="gam-p8bqe"/><path class="ece3hyfmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cbeth" /></template>
