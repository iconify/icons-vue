<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fdhc87aim.css';
import '../../css/b/bjaydi71w.css';
import '../../css/d/deitqfq6b.css';
import '../../css/x/xuok7lh9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fdhc87aim"/><circle class="bjaydi71w"/><circle class="deitqfq6b"/><circle class="xuok7lh9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:list" /></template>
