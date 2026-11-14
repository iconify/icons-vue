<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a90g9aclq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-filter" /></template>
<style>
.a90g9aclq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v6.754q-.571-.255-1.3-.254h-2.9q-1.873-.001-2.7 1.68q-.802 1.628.244 3.07h-2.812l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zm13.3 7.75h2.9q1.095-.001 1.579.982t-.185 1.851l-.938 1.22q-.156.202-.156.457v2.061q-.001.827-.724 1.227q-.722.4-1.423-.037l-.295-.184q-1.058-.661-1.058-1.908V18.26q0-.255-.155-.457l-.94-1.221q-.668-.867-.184-1.85t1.579-.982m-.001 1.5q-.161 0-.232.145q-.071.144.028.273l.938 1.221q.467.606.467 1.371v1.159q0 .416.352.636l.148.092V18.26q0-.765.466-1.371l.94-1.222q.098-.128.027-.272t-.233-.145z");
}

</style>
