<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w43uqtbnn.css';
import '../../css/o/o9nmldszk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w43uqtbnn"/><path clip-rule="evenodd" class="o9nmldszk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hashtag-square-bold" /></template>
