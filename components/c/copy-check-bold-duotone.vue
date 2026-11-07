<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xuvri7gtn.css';
import '../../css/m/mtplmt03a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xuvri7gtn"/><path class="mtplmt03a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-check-bold-duotone" /></template>
