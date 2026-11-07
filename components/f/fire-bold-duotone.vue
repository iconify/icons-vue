<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wole6hbze.css';
import '../../css/e/egno4qbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wole6hbze"/><path class="egno4qbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fire-bold-duotone" /></template>
