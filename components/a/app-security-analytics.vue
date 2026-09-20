<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfxpjhf8j.css';
import '../../css/q/qn4nzybbc.css';
import '../../css/o/owvyp-b9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sfxpjhf8j"/><path class="ouiIcon__fillSecondary qn4nzybbc"/><path class="owvyp-b9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:app-security-analytics" /></template>
