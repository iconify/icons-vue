<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at4a6-b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at4a6-b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-cancel" /></template>
