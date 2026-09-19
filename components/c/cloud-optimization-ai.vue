<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwgygxbhr.css';
import '../../css/s/s4iurdf1n.css';
import '../../css/l/li1rn3ywo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gwgygxbhr"/><path class="s4iurdf1n"/><path class="li1rn3ywo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-optimization-ai" /></template>
