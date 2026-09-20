<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/m/m40z4o.css';
import '../../css/v/v7zwrw.css';
import '../../css/z/z5rc8u.css';
import '../../css/k/kf9r7q.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c m40z4o"/><path class="a0m25c v7zwrw"/><path class="a0m25c z5rc8u"/><path class="a0m25c kf9r7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:align-center" /></template>
