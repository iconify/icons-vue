<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4i2ew1ke.css';
import '../../css/i/im-u8ub-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path clip-rule="evenodd" class="im-u8ub-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:gps-fixed-duotone" /></template>
