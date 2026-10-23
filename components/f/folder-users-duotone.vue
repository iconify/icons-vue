<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mm7o0g9ni.css';
import '../../css/d/dnbhgk0gf.css';
import '../../css/f/fjz2lp2no.css';
import '../../css/f/fqxr7ibpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mm7o0g9ni"/><path class="dnbhgk0gf"/><path class="fjz2lp2no"/><path class="fqxr7ibpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-users-duotone" /></template>
