<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvejj8wur.css';
import '../../css/k/kr2jicboj.css';
import '../../css/g/gtn46m-jg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="xvejj8wur"/><rect class="kr2jicboj"/><rect class="gtn46m-jg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:grid-row-top-filled" /></template>
