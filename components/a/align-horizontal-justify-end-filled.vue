<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/olh7nccxm.css';
import '../../css/m/m0esjaiqj.css';
import '../../css/j/jhkw66bqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="olh7nccxm"/><rect class="m0esjaiqj"/><path class="jhkw66bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:align-horizontal-justify-end-filled" /></template>
