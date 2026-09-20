<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv9_5wben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-delete-outline" /></template>
<style>
.lv9_5wben {
  fill: currentColor;
  d: path("M7 6v13zm3.866 14h-3.25q-.691 0-1.153-.462T6 18.384V6H5V5h4v-.77h6V5h4v1h-1v4.242q-.213-.048-.497-.068t-.503-.02V6H7v12.385q0 .23.192.423t.423.192h2.839q.073.275.188.538q.116.262.223.462m-1.211-3h.5q0-1.056.25-1.78l.25-.724V8h-1zm3.692-5.788q.213-.14.482-.281q.268-.14.518-.227V8h-1zm.222 9.22Q12.154 19.017 12.154 17t1.414-3.432T17 12.154t3.432 1.414T21.846 17t-1.414 3.432T17 21.846t-3.432-1.414m5.082-1.236l.546-.546l-1.811-1.811v-2.723h-.77v3.046z");
}

</style>
