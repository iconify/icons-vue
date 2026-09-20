<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/x/x5ao8m.css';
import '../../css/w/w4pkou.css';
import '../../css/g/ge04hr.css';
import '../../css/k/k4fugd.css';
import '../../css/p/pi14pi.css';
import '../../css/s/so-from-4.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c x5ao8m"/><path class="a0m25c w4pkou"/><path class="a0m25c ge04hr"/><path class="a0m25c k4fugd"/><path class="a0m25c pi14pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:bell-alert" /></template>
