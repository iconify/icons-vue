<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/l/ldq1rs.css';
import '../../css/k/kpnc8p.css';
import '../../css/l/l5mhfr.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ldq1rs"/><path class="a0m25c kpnc8p"/><path class="a0m25c l5mhfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-open-left" /></template>
