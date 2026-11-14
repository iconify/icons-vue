<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqc84ac6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bucket-hat" /></template>
<style>
.rqc84ac6h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.162 7.104l-.43 2.75q-.208 1.332.524 2.396H7q-.149 0-.287.057t-.243.163l-4 4q-.1.1-.157.229q-.03.068-.046.14q-.015.072-.017.146q-.001.074.012.147t.04.141q.026.069.066.131q.04.063.091.116q.052.053.112.095t.128.072Q5.843 19.063 12 19.063t9.301-1.376q.129-.057.229-.157q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-4-4q-.105-.106-.243-.163T17 12.25h-.256q.732-1.064.524-2.396l-.43-2.75q-.446-2.854-3.335-2.854h-3.006q-2.889 0-3.335 2.854");
}

</style>
