<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0o3zmben.css';
import '../../css/d/dn_h7dbug.css';
import '../../css/s/s9hvzfblf.css';
import '../../css/e/ebkr9o3it.css';
import '../../css/a/ai69p7nal.css';
import '../../css/k/kw-5oibaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<ellipse class="k0o3zmben"/><ellipse class="k0o3zmben"/><circle class="dn_h7dbug"/><ellipse class="s9hvzfblf"/><circle class="ebkr9o3it"/><circle class="ai69p7nal"/><circle class="kw-5oibaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:eye" /></template>
