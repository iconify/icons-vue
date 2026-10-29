<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g962xhd_j.css';
import '../../css/s/syrsg1b7q.css';
import '../../css/b/bgzw4_2lq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g962xhd_j wm-k"/><path class="syrsg1b7q wm-k"/><path class="bgzw4_2lq wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:alert-triangle" /></template>
