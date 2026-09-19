<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6wl26b_a.css';
import '../../css/g/gh_u1c66p.css';
import '../../css/z/z_3d8eb9h.css';
import '../../css/k/k0nky2wkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a6wl26b_a"/><circle class="gh_u1c66p"/><circle class="z_3d8eb9h"/><path class="k0nky2wkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:code-working-sharp" /></template>
