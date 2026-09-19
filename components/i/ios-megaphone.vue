<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m0j6vybkj.css';
import '../../css/v/vytfc2c_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m0j6vybkj"/><path class="vytfc2c_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-megaphone" /></template>
