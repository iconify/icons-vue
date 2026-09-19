<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpm4kob4e.css';
import '../../css/z/zbsn2h2kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="zpm4kob4e"/><path class="zbsn2h2kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:female-outline" /></template>
