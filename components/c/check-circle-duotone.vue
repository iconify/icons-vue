<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x63fcn5tz.css';
import '../../css/t/tymptoban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x63fcn5tz"/><path class="tymptoban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:check-circle-duotone" /></template>
