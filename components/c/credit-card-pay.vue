<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7a949o5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7a949o5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:credit-card-pay" /></template>
