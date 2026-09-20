<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsw5tr2lt.css';
import '../../css/i/ig6m21bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw5tr2lt"/><path class="ig6m21bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:crosshairs-24" /></template>
