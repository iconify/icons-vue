<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kazka8b2e.css';
import '../../css/b/b0insabyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="kazka8b2e"/><path clip-rule="evenodd" class="b0insabyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:del-alt-duotone" /></template>
