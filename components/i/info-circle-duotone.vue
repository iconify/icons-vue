<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l57giywpk.css';
import '../../css/f/fue51nqfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l57giywpk"/><path class="fue51nqfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:info-circle-duotone" /></template>
