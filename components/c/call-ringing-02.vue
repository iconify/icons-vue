<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh1xwcb2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rh1xwcb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-ringing-02" /></template>
