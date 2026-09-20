<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-tqdrbyb.css';
import '../../css/c/czuk_uaey.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path class="czuk_uaey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:magnifer-bold-duotone" /></template>
