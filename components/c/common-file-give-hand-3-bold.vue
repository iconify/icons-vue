<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5s1lcbbn.css';
import '../../css/d/dh2sg1pzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5s1lcbbn"/><path class="dh2sg1pzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:common-file-give-hand-3-bold" /></template>
