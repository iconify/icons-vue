<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gsi-nbz9w.css';
import '../../css/x/xpexa2b0b.css';
import '../../css/j/jinb6ibrg.css';
import '../../css/d/doz_8wbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gsi-nbz9w"/><circle class="xpexa2b0b"/><circle class="jinb6ibrg"/><circle class="doz_8wbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:list" /></template>
