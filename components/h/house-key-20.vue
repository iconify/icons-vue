<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7juawdew.css';
import '../../css/v/v0h2-7bys.css';
import '../../css/c/ctzl9ackg.css';
import '../../css/p/psrlxpb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p7juawdew"/><path class="v0h2-7bys"/><path class="ctzl9ackg"/><path class="psrlxpb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-key-20" /></template>
