<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q83hv0ath.css';
import '../../css/c/cj7oqvbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q83hv0ath"/><path class="cj7oqvbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-link" /></template>
