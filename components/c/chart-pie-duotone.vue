<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp348r2av.css';
import '../../css/j/jfqxk9a8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bp348r2av"/><path class="jfqxk9a8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chart-pie-duotone" /></template>
