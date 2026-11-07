<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln1f_4blw.css';
import '../../css/o/o1li7xbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln1f_4blw"/><path class="o1li7xbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-outline" /></template>
