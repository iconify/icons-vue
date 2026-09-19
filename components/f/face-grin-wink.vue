<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejpq9_evm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ejpq9_evm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-grin-wink" /></template>
