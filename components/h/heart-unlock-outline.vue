<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebl2e7rnn.css';
import '../../css/o/oj866ibnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl2e7rnn"/><path clip-rule="evenodd" class="oj866ibnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-unlock-outline" /></template>
