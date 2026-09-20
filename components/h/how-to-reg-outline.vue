<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdxqdrj2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:how-to-reg-outline" /></template>
<style>
.fdxqdrj2g {
  fill: currentColor;
  d: path("M2.942 18.616v-1.647q0-.767.377-1.232q.377-.466.954-.764q1.275-.65 2.51-1.004q1.234-.353 3.16-.353q.75 0 1.327.046q.578.046 1.022.138l-.903.904q-.275-.05-.653-.07q-.378-.018-.794-.018q-1.775 0-3.033.367t-2.159.867q-.456.24-.632.504q-.176.263-.176.615v.647h5.866l1 1zM15.3 19.708l-2.758-2.758l.708-.708l2.05 2.05l5.05-5.05l.708.708zm-7.48-9.2q-.878-.877-.878-2.123T7.82 6.26t2.123-.877t2.124.877t.876 2.123q0 1.247-.876 2.124q-.877.877-2.124.877q-1.246 0-2.123-.877m3.536-.711q.587-.587.587-1.412t-.587-1.413t-1.413-.587t-1.412.587t-.588 1.413t.588 1.412t1.412.588t1.413-.588M9.942 8.385");
}

</style>
