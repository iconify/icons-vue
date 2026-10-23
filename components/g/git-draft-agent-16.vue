<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odvyybvbi.css';
import '../../css/b/b2gj-9bfn.css';
import '../../css/c/c_sefrbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="odvyybvbi"/><path class="b2gj-9bfn"/><path class="c_sefrbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:git-draft-agent-16" /></template>
