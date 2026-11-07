<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrdvcwidb.css';
import '../../css/x/xlt2fc9tx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="xlt2fc9tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bolt-circle-bold-duotone" /></template>
