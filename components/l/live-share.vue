<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6xyl5_4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":25};
const content = `<path class="b6xyl5_4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:live-share" /></template>
