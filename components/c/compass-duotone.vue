<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn74v6bbn.css';
import '../../css/j/jjvt2sqaa.css';
import '../../css/c/cvu64vbfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn74v6bbn"/><path class="jjvt2sqaa"/><path class="cvu64vbfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:compass-duotone" /></template>
