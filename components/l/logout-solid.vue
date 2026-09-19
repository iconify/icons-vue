<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4nt_319i.css';
import '../../css/a/ac_y-5bbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4nt_319i"/><path class="ac_y-5bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:logout-solid" /></template>
