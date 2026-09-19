<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlg_s-bfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlg_s-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-show-15" /></template>
