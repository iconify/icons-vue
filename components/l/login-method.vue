<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r65zz4b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r65zz4b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:login-method" /></template>
