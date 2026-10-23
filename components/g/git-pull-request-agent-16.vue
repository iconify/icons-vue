<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7qv-mz-f.css';
import '../../css/e/e76qu_bjd.css';
import '../../css/i/ift_7p48t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="b7qv-mz-f"/><path class="e76qu_bjd"/><path class="ift_7p48t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-pull-request-agent-16" /></template>
