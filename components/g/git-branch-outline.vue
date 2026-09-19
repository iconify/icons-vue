<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znzucvy4i.css';
import '../../css/c/csk7b4xky.css';
import '../../css/k/k2bg6dpyt.css';
import '../../css/f/ftdas6b_c.css';
import '../../css/s/sw-xt6bsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="znzucvy4i"/><circle class="csk7b4xky"/><path class="k2bg6dpyt"/><circle class="ftdas6b_c"/><path class="sw-xt6bsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:git-branch-outline" /></template>
