<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae_fwibxk.css';
import '../../css/a/a_tf9kbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae_fwibxk"/><path class="a_tf9kbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-circle-outline" /></template>
