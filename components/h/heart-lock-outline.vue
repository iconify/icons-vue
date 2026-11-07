<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebl2e7rnn.css';
import '../../css/n/n84cny5hn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebl2e7rnn"/><path clip-rule="evenodd" class="n84cny5hn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-lock-outline" /></template>
