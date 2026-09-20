<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek71r_bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ek71r_bye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:intercom-alt" /></template>
