<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rc7r9_r6i.css';
import '../../css/p/pzwkoob0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rc7r9_r6i"/><path class="pzwkoob0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:activity" /></template>
