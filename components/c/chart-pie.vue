<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4yy3nb0m.css';
import '../../css/h/hxpwx2jys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4yy3nb0m"/><path class="hxpwx2jys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-pie" /></template>
