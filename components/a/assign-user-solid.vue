<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_lnf_n_d.css';
import '../../css/j/j5i82200f.css';
import '../../css/g/gllsilbfv.css';
import '../../css/v/vtrtxwlmf.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="clr-i-solid clr-i-solid-path-1 i_lnf_n_d"/><path class="clr-i-solid clr-i-solid-path-2 j5i82200f"/><path class="clr-i-solid clr-i-solid-path-3 gllsilbfv"/><path class="clr-i-solid clr-i-solid-path-4 vtrtxwlmf"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:assign-user-solid" /></template>
