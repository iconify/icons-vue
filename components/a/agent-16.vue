<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svnli_bhv.css';
import '../../css/y/y9urdac4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="svnli_bhv"/><path class="y9urdac4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:agent-16" /></template>
