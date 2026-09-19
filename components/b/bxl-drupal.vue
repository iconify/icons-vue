<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n2n0gkolt.css';
import '../../css/a/abdebfw2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2n0gkolt"/><path class="abdebfw2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-drupal" /></template>
