<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_ma8083f.css';
import '../../css/v/v9y5wi_ot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_ma8083f"/><path class="v9y5wi_ot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:exclamation-circle-light" /></template>
