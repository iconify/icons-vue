<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q74n_kb-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q74n_kb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-sharp-fill" /></template>
