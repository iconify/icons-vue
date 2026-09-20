<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4806ne8v.css';
import '../../css/j/jbx312dhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4806ne8v"/><path class="jbx312dhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:coin-solid" /></template>
