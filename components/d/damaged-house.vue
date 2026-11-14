<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcnlaxbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:damaged-house" /></template>
<style>
.lcnlaxbxq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m11.341 7.828l1.374-4.352q.026-.082.033-.168q.721.21 1.442.824l5.875 5.011q1.185 1.011 1.185 2.568v6.164q0 3.375-3.375 3.375h-5.374q.132 0 .255-.045q.07-.025.133-.064q.063-.038.118-.088t.098-.109t.075-.127t.048-.139q.018-.071.021-.145t-.008-.147t-.036-.142l-1.85-5.089l2.714-3.167q.044-.05.078-.108q.033-.057.056-.12q.024-.062.035-.128q.012-.065.012-.132t-.012-.132q-.011-.066-.035-.128q-.023-.063-.056-.12q-.034-.058-.078-.108zm1.158 13.422H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568L9.81 4.132q.69-.587 1.379-.805L9.785 7.774q-.029.091-.034.187q-.005.095.014.189t.061.18t.105.158l2.581 3.012l-2.581 3.012q-.065.076-.108.166t-.061.188t-.009.197q.008.1.042.193l2 5.5q.04.109.11.2t.164.158q.095.066.205.101t.225.035");
}

</style>
