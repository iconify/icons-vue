<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/geoim1bqf.css';
import '../../css/g/gj0fhibpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geoim1bqf"/><path clip-rule="evenodd" class="gj0fhibpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cassette-bold-duotone" /></template>
