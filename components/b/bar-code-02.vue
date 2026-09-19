<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md0vv3bmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md0vv3bmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:bar-code-02" /></template>
