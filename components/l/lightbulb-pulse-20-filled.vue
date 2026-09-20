<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nenrcxb9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-pulse-20-filled" /></template>
<style>
.nenrcxb9l {
  fill: currentColor;
  d: path("M12.69 16.606c-.185.77-.866 1.33-1.671 1.39l-.144.004h-1.75c-.819 0-1.535-.517-1.776-1.262l-.037-.133L6.928 15h6.145zm-4.113-4.631a1.5 1.5 0 0 0 2.765.196l.875-1.752c.283.365.719.581 1.183.581h1.59q-.484.721-1.194 1.395a.6.6 0 0 0-.145.211l-.026.082L13.31 14H6.69l-.314-1.312a.6.6 0 0 0-.17-.293A8.2 8.2 0 0 1 5.011 11H6.6a1.5 1.5 0 0 0 1.36-.872zM8.004 5a.5.5 0 0 1 .47.342l1.619 4.854l1.46-2.92a.5.5 0 0 1 .856-.063L13.66 9h1.84a.5.5 0 0 1 0 1h-2.1a.5.5 0 0 1-.41-.213l-.919-1.313l-1.624 3.25a.5.5 0 0 1-.922-.066L7.987 7.046l-.915 2.619c-.07.2-.26.335-.472.335H4.5a.5.5 0 0 1 0-1h1.745l1.283-3.665l.032-.072A.5.5 0 0 1 8.004 5M10 2c3.314 0 6 2.597 6 5.8l-.006.2h-1.813l-.952-1.36a1.5 1.5 0 0 0-2.57.19l-.382.76l-.854-2.565a1.5 1.5 0 0 0-2.839-.02L5.536 8H4.004L4 7.8l.003-.19C4.107 4.494 6.753 2 10 2");
}

</style>
