<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_wcs4pti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:crash-free" /></template>
<style>
.r_wcs4pti {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.546l-7.5-2.75Q12.133 1.75 12 1.75t-.258.046l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225V11q0 6.775 7.886 11.156q.083.046.176.07t.188.024t.188-.024t.176-.07Q20.25 17.775 20.25 11V5.25q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11m-8.772 8.63l4.22-4.443q.103-.108.239-.168q.137-.061.286-.065t.288.05t.248.156q.053.051.096.111q.042.061.072.128q.03.068.047.14q.016.072.018.146t-.011.146q-.012.073-.039.142q-.026.069-.066.132q-.039.062-.09.116l-4.75 5l-.014.013q-.105.106-.243.163T11 15t-.287-.057t-.243-.163l-2.5-2.5q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8.5 11t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
