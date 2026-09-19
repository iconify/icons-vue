<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbue6y19c.css';
import '../../css/h/hcbo7lb7t.css';
import '../../css/j/j-sz-bc4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbue6y19c"/><path class="hcbo7lb7t"/><circle class="j-sz-bc4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:git-cliff" /></template>
