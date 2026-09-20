<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2cyr5bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:group-remove" /></template>
<style>
.h2cyr5bhq {
  fill: currentColor;
  d: path("M12.692 11.335q.552-.589.776-1.364t.224-1.587t-.224-1.586t-.776-1.364q1.135.104 1.875.95q.74.847.74 2t-.74 2t-1.875.95m5 7.281v-1.692q0-.727-.265-1.395q-.265-.669-.838-1.101q1.025.315 1.872.903q.847.587.847 1.593v1.693zm4.616-8.115h-5v-1h5zm-15.739.008q-.877-.877-.877-2.123T6.57 6.26t2.123-.877t2.123.877t.877 2.123t-.877 2.124t-2.123.877t-2.123-.877m-4.877 8.108v-1.647q0-.619.36-1.158q.362-.54.971-.838q1.416-.679 2.833-1.018q1.417-.34 2.836-.34t2.837.34t2.833 1.018q.61.298.97.838q.36.539.36 1.158v1.647z");
}

</style>
