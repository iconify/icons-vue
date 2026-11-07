<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqtnv3iqd.css';
import '../../css/a/ayeh84bwp.css';
import '../../css/b/bcsn64b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqtnv3iqd"/><path class="ayeh84bwp"/><path clip-rule="evenodd" class="bcsn64b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:boombox-bold" /></template>
