<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sukwxlkix.css';
import '../../css/y/y5p1me9xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sukwxlkix"/><path class="y5p1me9xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-asia" /></template>
