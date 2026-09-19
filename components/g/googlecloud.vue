<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t76i9hy9s.css';
import '../../css/w/w3k2bgbvi.css';
import '../../css/m/mqimai2df.css';
import '../../css/i/ijb7gtbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="t76i9hy9s"/><path class="w3k2bgbvi"/><path class="mqimai2df"/><path class="ijb7gtbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:googlecloud" /></template>
