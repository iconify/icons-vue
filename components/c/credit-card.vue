<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hagmcibar.css';
import '../../css/l/ltxzfluea.css';
import '../../css/y/y8k8fzq5c.css';
import '../../css/v/vu_lpmb5d.css';
import '../../css/q/ql3pvabdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="hagmcibar"/><path class="ltxzfluea"/><path class="y8k8fzq5c"/><path class="vu_lpmb5d"/><path class="ql3pvabdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:credit-card" /></template>
